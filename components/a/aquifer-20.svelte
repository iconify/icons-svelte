<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijs8fxbia.css';
import '../../css/w/w8537imoy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ijs8fxbia"/><path class="w8537imoy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:aquifer-20" {...props}></Icon>
