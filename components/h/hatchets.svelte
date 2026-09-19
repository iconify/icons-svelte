<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbweqf9zu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pbweqf9zu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hatchets" {...props}></Icon>
