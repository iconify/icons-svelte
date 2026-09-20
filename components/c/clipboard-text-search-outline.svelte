<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8n05qlvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g8n05qlvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clipboard-text-search-outline" {...props}></Icon>
