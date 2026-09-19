<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmhqyt_6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hmhqyt_6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:distribute-horizontal-right" {...props}></Icon>
