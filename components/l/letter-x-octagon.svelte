<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2aqevb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h2aqevb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-x-octagon" {...props}></Icon>
