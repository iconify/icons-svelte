<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi47-hbwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vi47-hbwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:align-vertical-top" {...props}></Icon>
