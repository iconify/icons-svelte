<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd4-4tnnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hd4-4tnnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:mcdonalds" {...props}></Icon>
