<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utrfhtaas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="utrfhtaas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:logic-gate-nxor" {...props}></Icon>
