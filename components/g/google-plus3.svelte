<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9dkbobhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s9dkbobhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:google-plus3" {...props}></Icon>
