<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8df7qsuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r8df7qsuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:feathered-wing" {...props}></Icon>
