<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s40586bts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s40586bts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:chess-bishop" {...props}></Icon>
