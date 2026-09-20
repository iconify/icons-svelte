<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgl5e3brr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rgl5e3brr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:codeproject" {...props}></Icon>
