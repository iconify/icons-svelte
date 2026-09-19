<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwf780b5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qwf780b5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:explosive-meeting" {...props}></Icon>
