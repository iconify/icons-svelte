<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ey8xpjbce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ey8xpjbce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:partnership" {...props}></Icon>
