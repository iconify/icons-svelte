<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlz05eb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlz05eb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:content-save-minus-outline" {...props}></Icon>
