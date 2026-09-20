<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9m4w261h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="u9m4w261h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:mouth-lip" {...props}></Icon>
