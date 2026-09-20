<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjb5kkbmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yjb5kkbmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ocarina" {...props}></Icon>
