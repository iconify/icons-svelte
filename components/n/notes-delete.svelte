<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7iq23b_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l7iq23b_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:notes-delete" {...props}></Icon>
