<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgjv05bkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pgjv05bkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-text-rotation-down" {...props}></Icon>
