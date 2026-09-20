<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gm3u3j5lh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="gm3u3j5lh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alert-box" {...props}></Icon>
