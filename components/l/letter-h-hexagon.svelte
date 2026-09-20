<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkpsd5cgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nkpsd5cgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-h-hexagon" {...props}></Icon>
