<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uh5t2xsar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uh5t2xsar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:holy-water" {...props}></Icon>
