<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adoz3-3sq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="adoz3-3sq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:adobe-indesign" {...props}></Icon>
