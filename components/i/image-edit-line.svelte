<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpalc1bwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xpalc1bwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:image-edit-line" {...props}></Icon>
