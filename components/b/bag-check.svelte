<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc7k2r7yx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rc7k2r7yx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:bag-check" {...props}></Icon>
