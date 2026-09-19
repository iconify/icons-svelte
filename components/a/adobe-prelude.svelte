<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uumsez6hp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uumsez6hp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:adobe-prelude" {...props}></Icon>
