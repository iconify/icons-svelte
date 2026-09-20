<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j87cnacjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j87cnacjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:magnet" {...props}></Icon>
