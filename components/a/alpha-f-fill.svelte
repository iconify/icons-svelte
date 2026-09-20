<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbxlq0bic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="bbxlq0bic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alpha-f-fill" {...props}></Icon>
