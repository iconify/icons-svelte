<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxe8wwbmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vxe8wwbmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:input-search-solid" {...props}></Icon>
