<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4r-5wgdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h4r-5wgdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:flexible-lamp" {...props}></Icon>
