<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/typlptbgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="typlptbgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:bibtex" {...props}></Icon>
