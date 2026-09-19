<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8v-62bax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u8v-62bax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dolmen" {...props}></Icon>
