<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz58s7yxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xz58s7yxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:airport-plane-transit-solid" {...props}></Icon>
