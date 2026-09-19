<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufjel18om.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ufjel18om"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:corkscrew" {...props}></Icon>
