<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg3njrbjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yg3njrbjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:laundry-hand-wash" {...props}></Icon>
