<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aq4yjlbzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="aq4yjlbzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:maximize-stroke-16" {...props}></Icon>
