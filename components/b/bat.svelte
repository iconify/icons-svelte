<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xk5piibcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="xk5piibcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:bat" {...props}></Icon>
