<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ge6bl9sev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ge6bl9sev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:paperclip-gloss" {...props}></Icon>
