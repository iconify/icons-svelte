<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhaol57jf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yhaol57jf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:mecha-mask" {...props}></Icon>
