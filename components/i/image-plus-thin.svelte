<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzz7xk7cq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="uzz7xk7cq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:image-plus-thin" {...props}></Icon>
