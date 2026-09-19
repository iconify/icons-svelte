<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie1a0_6jd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ie1a0_6jd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:earth-americas" {...props}></Icon>
