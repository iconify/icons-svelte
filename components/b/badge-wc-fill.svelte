<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d70kyjb7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d70kyjb7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:badge-wc-fill" {...props}></Icon>
