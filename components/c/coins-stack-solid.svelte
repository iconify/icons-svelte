<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5f21kaay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f5f21kaay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:coins-stack-solid" {...props}></Icon>
