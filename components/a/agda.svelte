<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe7xcbbrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xe7xcbbrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:agda" {...props}></Icon>
