<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9v4tob1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h9v4tob1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:coins" {...props}></Icon>
