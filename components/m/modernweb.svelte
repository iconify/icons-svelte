<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wn5e1o2rf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wn5e1o2rf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:modernweb" {...props}></Icon>
