<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhlffspxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zhlffspxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:contacts-3-line" {...props}></Icon>
