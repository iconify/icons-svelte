<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h24t9d8sz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="h24t9d8sz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:buy-n-large" {...props}></Icon>
