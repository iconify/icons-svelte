<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vy07upbfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vy07upbfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:melting-metal" {...props}></Icon>
