<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l14xrabiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l14xrabiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:gems" {...props}></Icon>
