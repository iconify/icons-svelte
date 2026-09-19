<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojbe5ab3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ojbe5ab3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:air-zigzag" {...props}></Icon>
