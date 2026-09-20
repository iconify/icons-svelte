<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ai0e078-i.css';
import '../../css/i/ipw5bzbjz.css';
import '../../css/t/twp8wbb9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ai0e078-i"/><path class="ipw5bzbjz"/><path class="twp8wbb9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:listing-lab" {...props}></Icon>
