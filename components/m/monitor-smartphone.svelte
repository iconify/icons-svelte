<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwbkozmxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hwbkozmxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:monitor-smartphone" {...props}></Icon>
