<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddv-sj__j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ddv-sj__j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:counter" {...props}></Icon>
