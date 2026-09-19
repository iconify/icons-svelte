<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1rwnbp7q.css';
import '../../css/q/qru7a6bvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c1rwnbp7q"/><path class="qru7a6bvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:logo-glassdoor" {...props}></Icon>
