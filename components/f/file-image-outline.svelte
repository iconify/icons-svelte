<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vo9yh125o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vo9yh125o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-image-outline" {...props}></Icon>
