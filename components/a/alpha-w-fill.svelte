<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmaa6ub8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="zmaa6ub8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alpha-w-fill" {...props}></Icon>
