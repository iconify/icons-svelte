<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ah2m33b_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ah2m33b_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-arrow-left-outline" {...props}></Icon>
