<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw-fxp2ag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":488};
const content = `<path class="bw-fxp2ag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:forrst" {...props}></Icon>
