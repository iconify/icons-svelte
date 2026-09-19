<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw1zs5b9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iw1zs5b9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:editorconfig" {...props}></Icon>
