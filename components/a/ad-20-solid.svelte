<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f80vy0r6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="f80vy0r6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:ad-20-solid" {...props}></Icon>
