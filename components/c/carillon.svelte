<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksd0dwcta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ksd0dwcta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:carillon" {...props}></Icon>
