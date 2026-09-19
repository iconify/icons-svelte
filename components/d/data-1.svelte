<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewwnyrbqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ewwnyrbqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:data-1" {...props}></Icon>
