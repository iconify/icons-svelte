<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmc0o5h_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hmc0o5h_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:oyster" {...props}></Icon>
