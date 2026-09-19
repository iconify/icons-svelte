<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/poe4enb4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="poe4enb4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:raise-skeleton" {...props}></Icon>
