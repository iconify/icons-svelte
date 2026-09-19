<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjxp1tlnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fjxp1tlnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:barcode" {...props}></Icon>
