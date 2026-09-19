<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rp2bpywtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1026,"height":703};
const content = `<path class="rp2bpywtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:paperboat" {...props}></Icon>
