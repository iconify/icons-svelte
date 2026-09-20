<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xism68mgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xism68mgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:mingw-w64" {...props}></Icon>
