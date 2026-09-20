<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkty1mbtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bkty1mbtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-check-outline" {...props}></Icon>
