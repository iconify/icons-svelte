<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crrmgsbyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="crrmgsbyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alpha-d-fill" {...props}></Icon>
