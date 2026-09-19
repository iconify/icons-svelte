<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkhvx13gx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wkhvx13gx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:return-arrow" {...props}></Icon>
