<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlrl7bbnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xlrl7bbnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:external" {...props}></Icon>
