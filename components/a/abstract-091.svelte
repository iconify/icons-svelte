<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac27dvbvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ac27dvbvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-091" {...props}></Icon>
