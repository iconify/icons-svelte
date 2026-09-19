<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmmp82b-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="kmmp82b-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:droplet-outline" {...props}></Icon>
