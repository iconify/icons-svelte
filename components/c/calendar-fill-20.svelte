<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehhtqcchs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ehhtqcchs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:calendar-fill-20" {...props}></Icon>
