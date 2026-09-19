<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqoxu7b0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kqoxu7b0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:plum" {...props}></Icon>
