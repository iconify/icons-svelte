<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvmt2dbtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="jvmt2dbtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:chain-parallel" {...props}></Icon>
