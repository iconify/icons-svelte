<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4v3vwb8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c4v3vwb8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:load-balancer-listener" {...props}></Icon>
