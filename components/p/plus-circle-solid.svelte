<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xb6rkks4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xb6rkks4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:plus-circle-solid" {...props}></Icon>
