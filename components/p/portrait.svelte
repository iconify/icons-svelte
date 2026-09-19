<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pus2jacmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pus2jacmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:portrait" {...props}></Icon>
