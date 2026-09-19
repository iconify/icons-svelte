<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfeytobuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hfeytobuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:papyrus" {...props}></Icon>
