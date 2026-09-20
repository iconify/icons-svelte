<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u728x1lfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="u728x1lfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:battery-bolt" {...props}></Icon>
