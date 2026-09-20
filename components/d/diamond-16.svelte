<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyn_l9bao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xyn_l9bao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:diamond-16" {...props}></Icon>
