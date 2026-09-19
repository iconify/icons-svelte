<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aw9zkcbrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="aw9zkcbrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:enlarge2" {...props}></Icon>
