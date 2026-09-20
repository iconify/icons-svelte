<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/luj_xzb3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="luj_xzb3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:code-function" {...props}></Icon>
