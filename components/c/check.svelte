<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg79mza6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="eg79mza6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:check" {...props}></Icon>
