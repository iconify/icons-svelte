<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1c00mb_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b1c00mb_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:monitor-clean" {...props}></Icon>
