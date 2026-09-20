<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0ysv1t7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z0ysv1t7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-collapse-horizontal" {...props}></Icon>
