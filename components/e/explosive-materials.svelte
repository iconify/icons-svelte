<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ts5kodb7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ts5kodb7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:explosive-materials" {...props}></Icon>
