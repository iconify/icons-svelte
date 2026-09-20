<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgj2zbb7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sgj2zbb7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:cogs-solid" {...props}></Icon>
