<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-vi7nafh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-vi7nafh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-multiple-outline" {...props}></Icon>
