<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imp9hzbph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="imp9hzbph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:file-delta-filled" {...props}></Icon>
