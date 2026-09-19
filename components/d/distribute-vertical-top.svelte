<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oiwn7b8vb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oiwn7b8vb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:distribute-vertical-top" {...props}></Icon>
