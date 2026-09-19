<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4xv_n6bp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i4xv_n6bp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:face-very-happy-stroke-16" {...props}></Icon>
