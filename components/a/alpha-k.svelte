<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0c8ymouc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="i0c8ymouc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alpha-k" {...props}></Icon>
