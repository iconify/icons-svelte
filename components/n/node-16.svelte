<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6lrr_beh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s6lrr_beh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:node-16" {...props}></Icon>
