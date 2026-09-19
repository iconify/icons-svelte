<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tffa9ggeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tffa9ggeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:lotus" {...props}></Icon>
