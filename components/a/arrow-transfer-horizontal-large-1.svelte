<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgn2xtoqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wgn2xtoqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:arrow-transfer-horizontal-large-1" {...props}></Icon>
