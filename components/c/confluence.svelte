<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs_o-ybdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gs_o-ybdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:confluence" {...props}></Icon>
