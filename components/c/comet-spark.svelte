<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7xk1o6al.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u7xk1o6al"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:comet-spark" {...props}></Icon>
