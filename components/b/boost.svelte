<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgf2vobjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zgf2vobjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:boost" {...props}></Icon>
