<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7hfa2jyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a7hfa2jyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:moon" {...props}></Icon>
