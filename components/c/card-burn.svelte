<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2a4cd6kp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o2a4cd6kp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-burn" {...props}></Icon>
