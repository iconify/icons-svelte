<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jabfj5b2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jabfj5b2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:dead-tree" {...props}></Icon>
