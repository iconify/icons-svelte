<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/luw2295ii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="luw2295ii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:gavel" {...props}></Icon>
