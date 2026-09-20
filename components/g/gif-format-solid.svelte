<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/quv6j-zqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="quv6j-zqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:gif-format-solid" {...props}></Icon>
