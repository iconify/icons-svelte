<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i632_abrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i632_abrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:backpack-gloss" {...props}></Icon>
