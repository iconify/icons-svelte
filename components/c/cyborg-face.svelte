<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_o5gub2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v_o5gub2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cyborg-face" {...props}></Icon>
