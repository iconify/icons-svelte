<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-r11kbwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u-r11kbwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:nav-arrow-left-solid" {...props}></Icon>
