<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o44n3gbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o44n3gbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:evil-bat" {...props}></Icon>
