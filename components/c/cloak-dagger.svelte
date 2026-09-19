<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wg81n9b3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wg81n9b3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cloak-dagger" {...props}></Icon>
