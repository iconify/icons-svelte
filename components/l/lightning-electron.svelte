<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz3qcy9av.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vz3qcy9av"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:lightning-electron" {...props}></Icon>
