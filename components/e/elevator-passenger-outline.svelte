<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvrua7b7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wvrua7b7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:elevator-passenger-outline" {...props}></Icon>
