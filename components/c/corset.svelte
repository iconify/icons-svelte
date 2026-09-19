<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6l_umb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l6l_umb3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:corset" {...props}></Icon>
