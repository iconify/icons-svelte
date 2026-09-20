<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm-lq5bgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dm-lq5bgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:grid-vertical" {...props}></Icon>
