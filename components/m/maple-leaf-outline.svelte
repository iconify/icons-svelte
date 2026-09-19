<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_rwhnm2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="i_rwhnm2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:maple-leaf-outline" {...props}></Icon>
