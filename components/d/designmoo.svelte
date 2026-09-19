<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shye-ib9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":456};
const content = `<path class="shye-ib9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:designmoo" {...props}></Icon>
