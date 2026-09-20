<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vejx1kb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vejx1kb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:invoice-text" {...props}></Icon>
