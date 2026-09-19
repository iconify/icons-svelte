<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-r05mqvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r-r05mqvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:freemarker" {...props}></Icon>
