<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/al03c2bxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="al03c2bxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:array-date-time" {...props}></Icon>
