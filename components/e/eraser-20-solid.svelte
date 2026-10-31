<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ioepsabuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ioepsabuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:eraser-20-solid" {...props}></Icon>
