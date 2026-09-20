<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qns0hjbif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qns0hjbif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-arrow-right-outline" {...props}></Icon>
