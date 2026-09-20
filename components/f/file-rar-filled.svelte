<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwk8eab6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rwk8eab6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:file-rar-filled" {...props}></Icon>
