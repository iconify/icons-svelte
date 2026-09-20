<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdezwjb_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wdezwjb_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:bolt" {...props}></Icon>
