<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_14drd-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j_14drd-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-off-20" {...props}></Icon>
