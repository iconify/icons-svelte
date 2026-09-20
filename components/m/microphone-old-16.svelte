<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npn7ripfg.css';
import '../../css/f/fonv89syi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="npn7ripfg"/><path class="fonv89syi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:microphone-old-16" {...props}></Icon>
