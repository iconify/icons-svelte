<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3_0dkbiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h3_0dkbiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:center-circle" {...props}></Icon>
