<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwd3o3boq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pwd3o3boq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:align-horizontal-distribute" {...props}></Icon>
