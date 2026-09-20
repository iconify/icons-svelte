<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2_t1hbgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s2_t1hbgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:archive-arrow-up" {...props}></Icon>
