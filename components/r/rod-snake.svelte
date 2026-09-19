<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpg98ub8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="lpg98ub8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:rod-snake" {...props}></Icon>
