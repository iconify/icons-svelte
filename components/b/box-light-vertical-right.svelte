<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6s9z3b5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="i6s9z3b5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-vertical-right" {...props}></Icon>
