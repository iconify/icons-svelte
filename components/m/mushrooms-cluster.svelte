<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c18zojbqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c18zojbqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:mushrooms-cluster" {...props}></Icon>
