<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm63k1bpv.css';
import '../../css/g/ggrxmcksm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fm63k1bpv"/><path class="ggrxmcksm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:fullmoon" {...props}></Icon>
