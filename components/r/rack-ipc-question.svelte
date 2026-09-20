<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opq8e0bhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="opq8e0bhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:rack-ipc-question" {...props}></Icon>
