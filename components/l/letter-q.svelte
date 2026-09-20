<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xw72_ccft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xw72_ccft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-q" {...props}></Icon>
