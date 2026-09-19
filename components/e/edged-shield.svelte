<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7fq-fc7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j7fq-fc7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:edged-shield" {...props}></Icon>
