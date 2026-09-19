<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijvouq2eh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="ijvouq2eh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:file-circle-plus" {...props}></Icon>
