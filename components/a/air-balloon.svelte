<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by9j8n7zb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="by9j8n7zb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:air-balloon" {...props}></Icon>
