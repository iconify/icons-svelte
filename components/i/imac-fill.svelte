<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wur6xfp1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wur6xfp1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:imac-fill" {...props}></Icon>
