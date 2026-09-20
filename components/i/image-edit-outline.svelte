<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7_4cvbko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y7_4cvbko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:image-edit-outline" {...props}></Icon>
