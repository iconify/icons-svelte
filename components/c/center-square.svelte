<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv0wkklle.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cv0wkklle"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:center-square" {...props}></Icon>
