<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2nyl6bcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f2nyl6bcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:cheveron-left" {...props}></Icon>
