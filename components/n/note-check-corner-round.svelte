<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-gdrnhrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-gdrnhrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:note-check-corner-round" {...props}></Icon>
