<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1w9q6o5b.css';
import '../../css/d/d9t-opb0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c1w9q6o5b"/><path class="d9t-opb0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:badge-20-bold" {...props}></Icon>
