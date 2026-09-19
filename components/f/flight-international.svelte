<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o786i_bpn.css';
import '../../css/w/w_5dyix0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o786i_bpn"/><path class="w_5dyix0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:flight-international" {...props}></Icon>
