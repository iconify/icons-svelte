<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0b6ekbwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="j0b6ekbwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:grid" {...props}></Icon>
