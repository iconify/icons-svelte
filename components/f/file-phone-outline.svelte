<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yghokz6by.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yghokz6by"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-phone-outline" {...props}></Icon>
