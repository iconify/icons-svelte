<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk_enobxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rk_enobxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:call-2" {...props}></Icon>
