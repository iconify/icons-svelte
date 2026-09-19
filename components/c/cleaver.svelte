<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca-g7ac0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ca-g7ac0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cleaver" {...props}></Icon>
