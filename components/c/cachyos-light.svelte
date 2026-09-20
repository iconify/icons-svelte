<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojfp7w8vt.css';
import '../../css/s/sf89cnbpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ojfp7w8vt"/><path class="sf89cnbpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cachyos-light" {...props}></Icon>
