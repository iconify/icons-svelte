<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm1l5ccia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xm1l5ccia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:chevron-down-fill-16" {...props}></Icon>
