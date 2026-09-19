<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2tew1o-z.css';
import '../../css/c/cp8_n08jx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y2tew1o-z"/><path class="cp8_n08jx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:receipt" {...props}></Icon>
