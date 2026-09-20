<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_hb79b5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_hb79b5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:download-multiple-outline" {...props}></Icon>
