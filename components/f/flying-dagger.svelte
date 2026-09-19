<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5-7_mbpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v5-7_mbpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:flying-dagger" {...props}></Icon>
