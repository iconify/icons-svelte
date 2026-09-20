<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcoazubqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fcoazubqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:coding-apps-websites-programming-hold-code" {...props}></Icon>
