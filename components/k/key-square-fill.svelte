<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ieyuig28d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ieyuig28d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:key-square-fill" {...props}></Icon>
