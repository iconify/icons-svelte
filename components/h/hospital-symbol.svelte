<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vv6-mbbkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vv6-mbbkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:hospital-symbol" {...props}></Icon>
