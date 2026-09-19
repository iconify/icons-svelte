<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tn8z-11mg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="tn8z-11mg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:mobile-1-outline" {...props}></Icon>
