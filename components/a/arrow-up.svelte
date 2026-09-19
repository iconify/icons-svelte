<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/entb44w_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="entb44w_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:arrow-up" {...props}></Icon>
