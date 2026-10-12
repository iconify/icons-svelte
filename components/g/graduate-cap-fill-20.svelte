<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfu_5sb2s.css';
import '../../css/z/zu9il-bqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sfu_5sb2s"/><path class="zu9il-bqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:graduate-cap-fill-20" {...props}></Icon>
