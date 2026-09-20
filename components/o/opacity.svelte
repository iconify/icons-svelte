<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfjvo8v9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bfjvo8v9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:opacity" {...props}></Icon>
