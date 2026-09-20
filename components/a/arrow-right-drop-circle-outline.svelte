<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdhnu-7by.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hdhnu-7by"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-right-drop-circle-outline" {...props}></Icon>
