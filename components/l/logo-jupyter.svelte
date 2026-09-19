<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je6amzbhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="je6amzbhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:logo-jupyter" {...props}></Icon>
