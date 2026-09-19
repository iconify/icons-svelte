<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jv6fjxbjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":448};
const content = `<path class="jv6fjxbjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:hi5" {...props}></Icon>
