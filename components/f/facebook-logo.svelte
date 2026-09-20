<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku1ngabxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ku1ngabxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:facebook-logo" {...props}></Icon>
