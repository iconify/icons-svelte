<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ka754hyss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ka754hyss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:note-upload-corner-fill-round" {...props}></Icon>
