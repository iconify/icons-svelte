<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oks577bse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oks577bse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fast-arrow" {...props}></Icon>
