<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k50aywbip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k50aywbip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:machine-gun" {...props}></Icon>
