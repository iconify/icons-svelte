<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nba_ijb9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nba_ijb9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:map-pin-plus-inside" {...props}></Icon>
