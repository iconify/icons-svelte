<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xupq2nozy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xupq2nozy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:close-round" {...props}></Icon>
