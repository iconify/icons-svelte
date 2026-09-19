<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo4kztbeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xo4kztbeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:galaxy" {...props}></Icon>
