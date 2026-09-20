<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aadn1wbjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="aadn1wbjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:layers-1" {...props}></Icon>
