<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kavn-lb2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kavn-lb2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hammer-nails" {...props}></Icon>
