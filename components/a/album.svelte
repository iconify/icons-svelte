<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1e6c0b8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h1e6c0b8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:album" {...props}></Icon>
