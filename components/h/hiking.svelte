<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vig0qobll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vig0qobll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hiking" {...props}></Icon>
