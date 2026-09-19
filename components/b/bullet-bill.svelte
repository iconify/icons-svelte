<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd_c-xb3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vd_c-xb3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bullet-bill" {...props}></Icon>
