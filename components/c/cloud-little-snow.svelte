<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i52jnbbnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i52jnbbnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cloud-little-snow" {...props}></Icon>
