<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo0uuy-7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":448};
const content = `<path class="oo0uuy-7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:cloudapp" {...props}></Icon>
