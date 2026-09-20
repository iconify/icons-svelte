<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxi6bp23l.css';
import '../../css/f/fmxdhkgfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxi6bp23l"/><path class="fmxdhkgfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:arrow-circle-up" {...props}></Icon>
