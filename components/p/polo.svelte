<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d29xc20oi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d29xc20oi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:polo" {...props}></Icon>
