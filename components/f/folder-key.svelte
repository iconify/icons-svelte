<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-d9zgwqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-d9zgwqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-key" {...props}></Icon>
