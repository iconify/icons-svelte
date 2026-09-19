<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sg221mb-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sg221mb-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:evil-tower" {...props}></Icon>
