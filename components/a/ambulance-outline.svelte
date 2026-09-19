<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujsl2ac1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ujsl2ac1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:ambulance-outline" {...props}></Icon>
