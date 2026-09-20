<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyb9v64yf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dyb9v64yf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:face-scan-1-solid" {...props}></Icon>
