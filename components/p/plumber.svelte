<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3uiqy88h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="w3uiqy88h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:plumber" {...props}></Icon>
