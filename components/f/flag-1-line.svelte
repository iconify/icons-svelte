<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co4vrccrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="co4vrccrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flag-1-line" {...props}></Icon>
