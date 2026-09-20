<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddx_pdqze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ddx_pdqze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bank-transfer" {...props}></Icon>
