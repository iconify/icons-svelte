<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_prz6bcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l_prz6bcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:elephant-head" {...props}></Icon>
