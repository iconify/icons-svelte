<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd6a86fya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":150,"height":111};
const content = `<path class="jd6a86fya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kfc-dark" {...props}></Icon>
