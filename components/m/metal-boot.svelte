<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcdue44-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zcdue44-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:metal-boot" {...props}></Icon>
