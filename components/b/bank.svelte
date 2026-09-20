<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqhz4jlvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqhz4jlvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:bank" {...props}></Icon>
