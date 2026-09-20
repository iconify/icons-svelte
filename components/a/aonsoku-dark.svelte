<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2fjpkz3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x2fjpkz3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:aonsoku-dark" {...props}></Icon>
