<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3v5ssbyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l3v5ssbyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:lightning-frequency" {...props}></Icon>
