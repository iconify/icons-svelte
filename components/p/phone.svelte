<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdp92hz5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bdp92hz5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:phone" {...props}></Icon>
