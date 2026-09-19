<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixid9lbur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ixid9lbur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:letter-cc" {...props}></Icon>
