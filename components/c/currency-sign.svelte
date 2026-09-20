<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpnnzbcjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vpnnzbcjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:currency-sign" {...props}></Icon>
