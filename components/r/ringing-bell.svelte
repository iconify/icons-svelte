<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crnkngs6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="crnkngs6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ringing-bell" {...props}></Icon>
