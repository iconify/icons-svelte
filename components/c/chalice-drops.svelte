<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esv7tevcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="esv7tevcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:chalice-drops" {...props}></Icon>
