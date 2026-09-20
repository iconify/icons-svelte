<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1d8ujg_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="a1d8ujg_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alpha-c" {...props}></Icon>
