<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmwayqb3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kmwayqb3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:cvs" {...props}></Icon>
