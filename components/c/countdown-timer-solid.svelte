<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipj3-xb_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ipj3-xb_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:countdown-timer-solid" {...props}></Icon>
