<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3t0tdi0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="c3t0tdi0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:nfc-symbol" {...props}></Icon>
