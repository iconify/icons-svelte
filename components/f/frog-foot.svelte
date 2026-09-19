<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3-i6v9_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f3-i6v9_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:frog-foot" {...props}></Icon>
