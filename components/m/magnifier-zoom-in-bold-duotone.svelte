<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcjk-wbhz.css';
import '../../css/i/i3vvs1wnr.css';
import '../../css/z/zsypqnbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pcjk-wbhz"/><path class="i3vvs1wnr"/><path class="zsypqnbsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magnifier-zoom-in-bold-duotone" {...props}></Icon>
