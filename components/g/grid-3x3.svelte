<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2pojdx4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x2pojdx4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:grid-3x3" {...props}></Icon>
