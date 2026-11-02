<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc_hs6n6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pc_hs6n6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layers-line" {...props}></Icon>
