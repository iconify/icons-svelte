<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhemwg1as.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rhemwg1as"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:quora" {...props}></Icon>
