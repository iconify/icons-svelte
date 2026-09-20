<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/og-vwh8xj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="og-vwh8xj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:input-box-solid" {...props}></Icon>
