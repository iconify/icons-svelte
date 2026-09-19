<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss2drd55i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ss2drd55i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:blade-fall" {...props}></Icon>
