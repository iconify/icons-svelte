<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3odf057e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g3odf057e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:calendar2" {...props}></Icon>
