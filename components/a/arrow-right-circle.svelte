<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2ix4wils.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u2ix4wils"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-right-circle" {...props}></Icon>
