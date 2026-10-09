<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9w0v0j8h.css';
import '../../css/k/kyt7f6bbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n9w0v0j8h"/><path class="kyt7f6bbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:nacelle-20-bold" {...props}></Icon>
