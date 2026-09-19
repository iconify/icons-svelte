<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jytyqbb7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jytyqbb7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:letter-kk" {...props}></Icon>
