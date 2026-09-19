<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok6lomhrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ok6lomhrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:heart-hands-outline" {...props}></Icon>
