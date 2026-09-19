<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdi7so47j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qdi7so47j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:all-seeing-eye" {...props}></Icon>
