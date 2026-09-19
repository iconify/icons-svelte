<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_rkbpwtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p_rkbpwtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bright-explosion" {...props}></Icon>
