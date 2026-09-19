<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzgvacb1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nzgvacb1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:if-action" {...props}></Icon>
