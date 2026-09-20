<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qh9zt9nng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qh9zt9nng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:bookmark-solid" {...props}></Icon>
