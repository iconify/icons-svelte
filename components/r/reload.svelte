<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8xm3vb2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j8xm3vb2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:reload" {...props}></Icon>
