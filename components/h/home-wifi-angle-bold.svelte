<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2ft5u2rt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w2ft5u2rt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:home-wifi-angle-bold" {...props}></Icon>
