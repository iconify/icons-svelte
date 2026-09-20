<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vn9m6vbtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vn9m6vbtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:phone" {...props}></Icon>
