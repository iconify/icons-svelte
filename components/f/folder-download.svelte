<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw1cj-brk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gw1cj-brk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-download" {...props}></Icon>
