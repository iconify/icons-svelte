<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r07u4nbzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r07u4nbzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:cbs-sports" {...props}></Icon>
