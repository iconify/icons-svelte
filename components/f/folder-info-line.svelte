<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gba0ul-cb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gba0ul-cb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folder-info-line" {...props}></Icon>
