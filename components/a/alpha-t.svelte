<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd5n0mazb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="kd5n0mazb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alpha-t" {...props}></Icon>
