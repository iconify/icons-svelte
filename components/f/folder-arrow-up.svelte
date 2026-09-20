<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4c77e6cx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p4c77e6cx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-arrow-up" {...props}></Icon>
