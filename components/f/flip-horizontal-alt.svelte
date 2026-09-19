<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7gesdbtz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e7gesdbtz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:flip-horizontal-alt" {...props}></Icon>
