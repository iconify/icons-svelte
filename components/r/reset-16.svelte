<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_0yjrl9v.css';
import '../../css/m/mxgiipv4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s_0yjrl9v"/><path class="mxgiipv4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:reset-16" {...props}></Icon>
