<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrzf860or.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jrzf860or"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-information-outline" {...props}></Icon>
