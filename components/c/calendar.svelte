<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tm9_03bcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tm9_03bcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:calendar" {...props}></Icon>
