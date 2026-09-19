<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6rqg_c8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i6rqg_c8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:pop-in" {...props}></Icon>
