<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqhp6dbju.css';
import '../../css/p/pzbcwvb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kqhp6dbju"/><path class="pzbcwvb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:location-heart-filled" {...props}></Icon>
