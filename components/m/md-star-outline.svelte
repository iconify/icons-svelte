<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx54llnwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hx54llnwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-star-outline" {...props}></Icon>
