<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9p9bs7fm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="x9p9bs7fm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:bandcamp" {...props}></Icon>
