<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn_ysqnph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hn_ysqnph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:product-hunt" {...props}></Icon>
