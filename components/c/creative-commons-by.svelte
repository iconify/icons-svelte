<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg7x33b0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cg7x33b0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:creative-commons-by" {...props}></Icon>
