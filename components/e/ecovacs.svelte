<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0aqn2g6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0aqn2g6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ecovacs" {...props}></Icon>
