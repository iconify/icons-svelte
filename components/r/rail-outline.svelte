<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d30ixlj3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d30ixlj3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:rail-outline" {...props}></Icon>
