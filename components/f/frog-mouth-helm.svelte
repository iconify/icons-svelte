<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehgrw2b_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ehgrw2b_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:frog-mouth-helm" {...props}></Icon>
