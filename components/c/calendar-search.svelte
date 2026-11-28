<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv2z-r7bz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kv2z-r7bz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:calendar-search" {...props}></Icon>
