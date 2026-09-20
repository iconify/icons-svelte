<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw1j5ebjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qw1j5ebjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:note-filled" {...props}></Icon>
