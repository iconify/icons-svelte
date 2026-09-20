<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkb3agx2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xkb3agx2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:price-tag-3-fill" {...props}></Icon>
