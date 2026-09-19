<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il99x8wzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="il99x8wzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:letter-dd" {...props}></Icon>
