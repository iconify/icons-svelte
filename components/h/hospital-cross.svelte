<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3b9rxbzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a3b9rxbzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hospital-cross" {...props}></Icon>
