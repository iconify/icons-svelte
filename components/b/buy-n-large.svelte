<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4t4632zq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o4t4632zq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:buy-n-large" {...props}></Icon>
