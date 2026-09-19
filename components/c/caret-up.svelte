<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1-enbb8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w1-enbb8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:caret-up" {...props}></Icon>
