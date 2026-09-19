<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvkc56lvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="uvkc56lvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:grid-sm-outline" {...props}></Icon>
