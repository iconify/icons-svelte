<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lumw3fbrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="lumw3fbrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:leaf-outline" {...props}></Icon>
