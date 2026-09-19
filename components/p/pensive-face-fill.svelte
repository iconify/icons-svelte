<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3kr0wb-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h3kr0wb-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:pensive-face-fill" {...props}></Icon>
