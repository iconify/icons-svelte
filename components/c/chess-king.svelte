<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phkpb-2vq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="phkpb-2vq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:chess-king" {...props}></Icon>
