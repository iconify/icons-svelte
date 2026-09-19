<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks7t_sbrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ks7t_sbrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:clock-tower" {...props}></Icon>
