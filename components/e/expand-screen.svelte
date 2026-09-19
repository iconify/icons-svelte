<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wn2j9uzdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wn2j9uzdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:expand-screen" {...props}></Icon>
