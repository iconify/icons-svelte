<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi3dao0ht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bi3dao0ht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:armchair" {...props}></Icon>
