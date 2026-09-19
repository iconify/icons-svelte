<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr0t2jb7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tr0t2jb7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-2-hearts" {...props}></Icon>
