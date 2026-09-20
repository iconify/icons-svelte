<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwhfntbgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nwhfntbgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:double-chevron-right" {...props}></Icon>
