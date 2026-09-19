<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dal1jpsba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dal1jpsba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:revolt" {...props}></Icon>
