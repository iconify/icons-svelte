<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ed-1j8bav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ed-1j8bav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:arrow-bottom" {...props}></Icon>
