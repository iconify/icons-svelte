<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sz9xce7wc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sz9xce7wc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:goodreads" {...props}></Icon>
