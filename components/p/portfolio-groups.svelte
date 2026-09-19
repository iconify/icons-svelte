<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpl92qbfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dpl92qbfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:portfolio-groups" {...props}></Icon>
