<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw_x7sqyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lw_x7sqyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:horn-internal" {...props}></Icon>
