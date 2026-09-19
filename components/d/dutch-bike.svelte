<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8ioll_bk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u8ioll_bk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dutch-bike" {...props}></Icon>
