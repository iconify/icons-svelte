<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glr4g87vl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="glr4g87vl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:budded-latin-cross" {...props}></Icon>
