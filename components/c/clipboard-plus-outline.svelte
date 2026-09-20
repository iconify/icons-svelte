<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbxuu6bvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tbxuu6bvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clipboard-plus-outline" {...props}></Icon>
