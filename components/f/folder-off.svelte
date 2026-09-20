<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3wo63bsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c3wo63bsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-off" {...props}></Icon>
