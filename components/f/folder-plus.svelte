<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewug2tztv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ewug2tztv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:folder-plus" {...props}></Icon>
