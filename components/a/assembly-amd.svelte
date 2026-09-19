<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkp9dgb8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pkp9dgb8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:assembly-amd" {...props}></Icon>
