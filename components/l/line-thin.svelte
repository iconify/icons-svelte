<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7hje7b3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o7hje7b3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:line-thin" {...props}></Icon>
