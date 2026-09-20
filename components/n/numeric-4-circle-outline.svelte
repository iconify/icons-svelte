<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzi_0qbmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzi_0qbmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric-4-circle-outline" {...props}></Icon>
