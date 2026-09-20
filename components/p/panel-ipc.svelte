<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j71h0-ger.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j71h0-ger"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:panel-ipc" {...props}></Icon>
