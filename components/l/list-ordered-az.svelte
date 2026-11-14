<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vphx_6btq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vphx_6btq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:list-ordered-az" {...props}></Icon>
