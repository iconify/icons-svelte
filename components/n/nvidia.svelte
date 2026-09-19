<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqe0vpyij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kqe0vpyij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:nvidia" {...props}></Icon>
