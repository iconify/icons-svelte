<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc6q_garz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cc6q_garz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:8mb-local-dark" {...props}></Icon>
