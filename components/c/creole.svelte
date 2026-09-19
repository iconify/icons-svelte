<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_p2r6ryq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s_p2r6ryq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:creole" {...props}></Icon>
