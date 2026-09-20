<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwl9ebcyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rwl9ebcyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:cloud-drizzle" {...props}></Icon>
