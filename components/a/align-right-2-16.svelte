<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vr50_qbod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vr50_qbod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:align-right-2-16" {...props}></Icon>
