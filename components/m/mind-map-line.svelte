<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eya_1n8bo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eya_1n8bo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mind-map-line" {...props}></Icon>
