<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp6yu-55v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sp6yu-55v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chart-3d" {...props}></Icon>
