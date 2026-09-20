<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euxmq9mxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="euxmq9mxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:rewind-filled" {...props}></Icon>
