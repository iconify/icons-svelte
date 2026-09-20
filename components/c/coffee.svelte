<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6jw2n68b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j6jw2n68b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:coffee" {...props}></Icon>
