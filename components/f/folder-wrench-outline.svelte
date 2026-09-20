<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpi8iibkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cpi8iibkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-wrench-outline" {...props}></Icon>
