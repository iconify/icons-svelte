<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pq8l11ltu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pq8l11ltu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:logo-vercel" {...props}></Icon>
