<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i064ubcxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="i064ubcxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alpha-t-fill" {...props}></Icon>
