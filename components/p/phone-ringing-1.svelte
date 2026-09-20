<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ton_gr_8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ton_gr_8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:phone-ringing-1" {...props}></Icon>
