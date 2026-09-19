<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdggac0rb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zdggac0rb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:buildings-fill" {...props}></Icon>
