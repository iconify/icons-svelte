<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zoe7uff-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zoe7uff-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:brain-line" {...props}></Icon>
