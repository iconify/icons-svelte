<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6oxyd10e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p6oxyd10e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:finance" {...props}></Icon>
