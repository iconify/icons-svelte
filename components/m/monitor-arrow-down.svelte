<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyb2-dbjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uyb2-dbjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:monitor-arrow-down" {...props}></Icon>
