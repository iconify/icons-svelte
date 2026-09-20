<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9pr4_bcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p9pr4_bcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:douban-line" {...props}></Icon>
