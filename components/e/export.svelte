<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dj-g8ac3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dj-g8ac3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:export" {...props}></Icon>
