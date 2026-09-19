<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_lt4yb4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1025};
const content = `<path class="k_lt4yb4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:refreshalt" {...props}></Icon>
