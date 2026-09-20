<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv45fpvfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gv45fpvfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:materialious-dark" {...props}></Icon>
