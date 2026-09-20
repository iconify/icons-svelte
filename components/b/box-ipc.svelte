<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjo5o7goe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tjo5o7goe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:box-ipc" {...props}></Icon>
