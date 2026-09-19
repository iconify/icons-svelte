<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb-8p7lsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eb-8p7lsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:metronome" {...props}></Icon>
