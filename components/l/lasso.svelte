<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xri_i47lq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xri_i47lq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:lasso" {...props}></Icon>
