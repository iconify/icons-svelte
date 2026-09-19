<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsotg_bjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xsotg_bjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-shield" {...props}></Icon>
