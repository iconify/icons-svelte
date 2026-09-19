<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etw1sjxsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="etw1sjxsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:iceland" {...props}></Icon>
