<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynm6qkaqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ynm6qkaqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:padlock" {...props}></Icon>
