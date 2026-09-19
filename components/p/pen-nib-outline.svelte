<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id6rdh24x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="id6rdh24x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:pen-nib-outline" {...props}></Icon>
