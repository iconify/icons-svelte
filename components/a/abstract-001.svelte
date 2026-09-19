<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsb-o9f4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gsb-o9f4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-001" {...props}></Icon>
