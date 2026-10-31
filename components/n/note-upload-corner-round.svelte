<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wy6azchko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wy6azchko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:note-upload-corner-round" {...props}></Icon>
