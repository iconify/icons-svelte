<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmrbxm3qn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vmrbxm3qn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:border-bottom-variant" {...props}></Icon>
