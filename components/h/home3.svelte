<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urk_5fbdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="urk_5fbdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:home3" {...props}></Icon>
