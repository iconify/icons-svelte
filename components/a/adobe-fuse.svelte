<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9iipm8aj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="c9iipm8aj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:adobe-fuse" {...props}></Icon>
