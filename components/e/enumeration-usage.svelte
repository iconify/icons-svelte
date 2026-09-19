<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo6c3-5uk.css';
import '../../css/f/f-7sbkbnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fo6c3-5uk"/><path class="f-7sbkbnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:enumeration-usage" {...props}></Icon>
