<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bz0m0tbhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bz0m0tbhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bandage" {...props}></Icon>
