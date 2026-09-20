<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc2up6cvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="bc2up6cvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alpha-p-fill" {...props}></Icon>
