<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iiimvjm9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iiimvjm9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:porcelain-vase" {...props}></Icon>
