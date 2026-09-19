<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5qakfbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="a5qakfbez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:hanukiah" {...props}></Icon>
