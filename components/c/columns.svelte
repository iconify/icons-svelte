<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-o3-66fq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b-o3-66fq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:columns" {...props}></Icon>
