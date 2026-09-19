<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtzx5nj7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dtzx5nj7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-shuffle" {...props}></Icon>
