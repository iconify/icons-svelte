<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy4k87b1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xy4k87b1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:image-filter-center-focus-weak" {...props}></Icon>
