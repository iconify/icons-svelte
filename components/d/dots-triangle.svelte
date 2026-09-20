<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clsr5qrqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="clsr5qrqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:dots-triangle" {...props}></Icon>
