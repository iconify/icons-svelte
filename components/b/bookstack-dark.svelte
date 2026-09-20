<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7w8d9joa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i7w8d9joa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bookstack-dark" {...props}></Icon>
