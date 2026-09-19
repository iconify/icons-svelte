<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-mw4h6ng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o-mw4h6ng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:horned-skull" {...props}></Icon>
