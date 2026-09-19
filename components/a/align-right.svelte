<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ketm56k_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ketm56k_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:align-right" {...props}></Icon>
