<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6ak47bht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u6ak47bht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:green-power" {...props}></Icon>
