<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_76ry0sr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="i_76ry0sr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:corners-pointing-out-20-solid" {...props}></Icon>
