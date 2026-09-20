<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r36w5t33e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r36w5t33e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:d3js-logo-solid" {...props}></Icon>
