<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4za4obho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m4za4obho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pointy-hat" {...props}></Icon>
