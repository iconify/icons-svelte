<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duu6_4t6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duu6_4t6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-bottom-right-thin" {...props}></Icon>
