<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx-a9nbrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xx-a9nbrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:message-delete" {...props}></Icon>
