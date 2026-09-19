<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stmo5bbqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="stmo5bbqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fission" {...props}></Icon>
