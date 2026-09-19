<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd6_5ub6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jd6_5ub6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:incomplete-error" {...props}></Icon>
