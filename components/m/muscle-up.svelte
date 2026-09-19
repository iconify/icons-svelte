<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwb7bbe5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jwb7bbe5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:muscle-up" {...props}></Icon>
