<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cag2ndsks.css';
import '../../css/p/pdncx1b3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cag2ndsks"/><path class="pdncx1b3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:map" {...props}></Icon>
