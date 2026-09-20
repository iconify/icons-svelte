<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-b7ilbqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z-b7ilbqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:paypal-remix" {...props}></Icon>
