<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfz2y4bgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yfz2y4bgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:new-relic" {...props}></Icon>
