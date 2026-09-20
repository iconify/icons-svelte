<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ev4r-7fft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ev4r-7fft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:check-circled" {...props}></Icon>
