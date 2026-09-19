<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb6wl9bmp.css';
import '../../css/j/jm1-sfbtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kb6wl9bmp"/><path class="jm1-sfbtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:chevron-circle-down-alt" {...props}></Icon>
