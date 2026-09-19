<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm15w3b5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qm15w3b5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:axe-sword" {...props}></Icon>
