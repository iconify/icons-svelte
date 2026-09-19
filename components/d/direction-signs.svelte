<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7w0psy3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t7w0psy3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:direction-signs" {...props}></Icon>
