<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdm5qgbme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cdm5qgbme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:annotation-info" {...props}></Icon>
