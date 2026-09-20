<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yj9-b1boq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yj9-b1boq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:eye-circle" {...props}></Icon>
