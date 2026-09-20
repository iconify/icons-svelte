<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u95q25xah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u95q25xah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:note-1-off" {...props}></Icon>
