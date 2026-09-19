<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd27vzkue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pd27vzkue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:octoman" {...props}></Icon>
