<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vidas8bkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vidas8bkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:kick-scooter-with-power-cord" {...props}></Icon>
