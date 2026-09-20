<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6bz4cbnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="p6bz4cbnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:fingerprint-1-solid" {...props}></Icon>
