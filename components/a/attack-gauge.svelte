<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocwji-sks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ocwji-sks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:attack-gauge" {...props}></Icon>
