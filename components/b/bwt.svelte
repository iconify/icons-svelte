<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vo4n4ebjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vo4n4ebjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bwt" {...props}></Icon>
