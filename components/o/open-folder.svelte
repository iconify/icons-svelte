<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds166cc_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ds166cc_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:open-folder" {...props}></Icon>
