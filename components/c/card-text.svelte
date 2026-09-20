<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu1x-2owc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yu1x-2owc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:card-text" {...props}></Icon>
