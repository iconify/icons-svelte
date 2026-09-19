<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r209j7-tl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r209j7-tl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:abc-iview" {...props}></Icon>
