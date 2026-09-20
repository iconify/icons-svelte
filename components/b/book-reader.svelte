<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgf1dgwdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jgf1dgwdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:book-reader" {...props}></Icon>
