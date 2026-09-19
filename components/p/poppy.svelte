<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud59pdg3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ud59pdg3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:poppy" {...props}></Icon>
