<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q50x75u1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q50x75u1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:chevron-bar-contract" {...props}></Icon>
