<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss_8yf0lc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ss_8yf0lc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:clouddown" {...props}></Icon>
