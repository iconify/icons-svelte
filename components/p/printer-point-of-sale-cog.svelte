<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzxstkb2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jzxstkb2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:printer-point-of-sale-cog" {...props}></Icon>
