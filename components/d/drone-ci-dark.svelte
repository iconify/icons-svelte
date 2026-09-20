<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4t0l33wp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x4t0l33wp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:drone-ci-dark" {...props}></Icon>
