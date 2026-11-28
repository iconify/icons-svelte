<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhq0xobbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lhq0xobbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:map-pins" {...props}></Icon>
