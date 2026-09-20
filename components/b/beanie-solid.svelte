<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikdx8cccy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ikdx8cccy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:beanie-solid" {...props}></Icon>
