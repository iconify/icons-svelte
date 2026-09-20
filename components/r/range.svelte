<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1tb8xbet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="y1tb8xbet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:range" {...props}></Icon>
