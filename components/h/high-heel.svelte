<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3884ntkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x3884ntkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:high-heel" {...props}></Icon>
