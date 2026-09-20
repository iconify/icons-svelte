<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxcgr-bcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="rxcgr-bcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alpha-g-fill" {...props}></Icon>
