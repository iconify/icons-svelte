<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysraz6bcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ysraz6bcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:data-class" {...props}></Icon>
