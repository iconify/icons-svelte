<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbd3g8bmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zbd3g8bmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hole" {...props}></Icon>
