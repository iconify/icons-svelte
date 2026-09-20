<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ix-pf_jrx.css';
import '../../css/r/r3q5yh9_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ix-pf_jrx"/><path class="r3q5yh9_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kubernetes" {...props}></Icon>
