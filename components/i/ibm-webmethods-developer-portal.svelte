<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6yn1hbsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q6yn1hbsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-webmethods-developer-portal" {...props}></Icon>
