<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i12ji_bzg.css';
import '../../css/b/btytjgehb.css';
import '../../css/x/xrhckqv-s.css';
import '../../css/m/myh4p8ksh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i12ji_bzg"/><path class="btytjgehb"/><ellipse class="xrhckqv-s"/><path class="myh4p8ksh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:folder-pesde-open" {...props}></Icon>
