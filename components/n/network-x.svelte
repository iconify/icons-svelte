<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ruwa10bqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ruwa10bqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:network-x" {...props}></Icon>
