<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/boj-c4biw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="boj-c4biw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:heart-wings" {...props}></Icon>
