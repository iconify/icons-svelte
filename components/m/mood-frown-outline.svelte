<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7ub_xb0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="u7ub_xb0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:mood-frown-outline" {...props}></Icon>
