<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyv_syg-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="hyv_syg-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:phone-ringing-1" {...props}></Icon>
