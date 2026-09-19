<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-e5_bbid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h-e5_bbid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:go-old" {...props}></Icon>
