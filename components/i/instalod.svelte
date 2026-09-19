<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgm3qwbst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tgm3qwbst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:instalod" {...props}></Icon>
