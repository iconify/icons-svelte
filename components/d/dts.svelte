<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udzib8bak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udzib8bak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:dts" {...props}></Icon>
