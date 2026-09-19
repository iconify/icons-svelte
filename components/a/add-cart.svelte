<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0a_18bcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d0a_18bcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:add-cart" {...props}></Icon>
