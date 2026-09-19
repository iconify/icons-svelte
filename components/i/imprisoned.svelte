<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfdxk_9-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vfdxk_9-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:imprisoned" {...props}></Icon>
