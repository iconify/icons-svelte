<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns7q5-h7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ns7q5-h7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:curved-line-dashed" {...props}></Icon>
