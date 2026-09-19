<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo6c3-5uk.css';
import '../../css/t/t9axjb05q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fo6c3-5uk"/><path class="t9axjb05q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:enumeration-definition" {...props}></Icon>
