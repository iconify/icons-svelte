<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unp-q8byn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="unp-q8byn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:greenhouse" {...props}></Icon>
