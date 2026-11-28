<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwh_2034p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="jwh_2034p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:music-notes-slash-bold" {...props}></Icon>
