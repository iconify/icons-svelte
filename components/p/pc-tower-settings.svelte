<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2cph-6yb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="n2cph-6yb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:pc-tower-settings" {...props}></Icon>
