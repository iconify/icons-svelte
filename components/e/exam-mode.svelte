<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x76te59bh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x76te59bh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:exam-mode" {...props}></Icon>
