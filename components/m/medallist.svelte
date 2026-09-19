<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isz-uwbjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="isz-uwbjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:medallist" {...props}></Icon>
