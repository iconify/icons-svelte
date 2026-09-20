<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0ovpsbko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="y0ovpsbko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:arrow-up-circle" {...props}></Icon>
