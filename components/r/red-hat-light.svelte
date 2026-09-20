<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dg10sto-u.css';
import '../../css/h/h0ngerbrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dg10sto-u"/><path class="h0ngerbrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:red-hat-light" {...props}></Icon>
