<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzo58fddj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zzo58fddj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:military-camp" {...props}></Icon>
