<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rik9w5jvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rik9w5jvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:peloton" {...props}></Icon>
