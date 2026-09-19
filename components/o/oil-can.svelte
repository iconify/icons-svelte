<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq1fj96eh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mq1fj96eh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:oil-can" {...props}></Icon>
