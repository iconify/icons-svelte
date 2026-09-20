<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd6l2pibj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zd6l2pibj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bathtub-outline" {...props}></Icon>
