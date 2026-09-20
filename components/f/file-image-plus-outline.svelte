<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chq9vvbwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chq9vvbwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-image-plus-outline" {...props}></Icon>
