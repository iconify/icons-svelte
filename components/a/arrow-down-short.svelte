<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo9n_mj0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xo9n_mj0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-down-short" {...props}></Icon>
