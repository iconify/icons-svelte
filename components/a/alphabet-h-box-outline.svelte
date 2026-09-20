<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmylqvzxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hmylqvzxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alphabet-h-box-outline" {...props}></Icon>
