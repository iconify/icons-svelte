<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkpht6big.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkpht6big"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:corner-left-up-solid" {...props}></Icon>
