<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owm_lybuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="owm_lybuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-028" {...props}></Icon>
