<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug-mjlbkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ug-mjlbkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:diagram-3" {...props}></Icon>
