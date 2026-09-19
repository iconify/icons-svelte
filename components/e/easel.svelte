<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aeljdvbmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aeljdvbmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:easel" {...props}></Icon>
