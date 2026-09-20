<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpn0lkbck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bpn0lkbck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:react" {...props}></Icon>
