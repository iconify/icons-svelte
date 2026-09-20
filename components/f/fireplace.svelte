<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht007_bvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ht007_bvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:fireplace" {...props}></Icon>
