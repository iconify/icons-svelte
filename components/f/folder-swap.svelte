<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yi-2hybse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yi-2hybse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-swap" {...props}></Icon>
