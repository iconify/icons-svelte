<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc_p19a1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tc_p19a1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ignidash" {...props}></Icon>
