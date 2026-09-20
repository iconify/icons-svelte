<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tacc1hwhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tacc1hwhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-off-outline" {...props}></Icon>
