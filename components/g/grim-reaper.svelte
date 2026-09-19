<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo3c_0mes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xo3c_0mes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:grim-reaper" {...props}></Icon>
