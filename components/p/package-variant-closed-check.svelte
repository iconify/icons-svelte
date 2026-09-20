<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw6b44bqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iw6b44bqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:package-variant-closed-check" {...props}></Icon>
