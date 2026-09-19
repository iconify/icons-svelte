<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_aolf-cf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":315,"height":512};
const content = `<path class="l_aolf-cf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:lean" {...props}></Icon>
