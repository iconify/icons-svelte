<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu4dusbhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fu4dusbhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:monk-face" {...props}></Icon>
