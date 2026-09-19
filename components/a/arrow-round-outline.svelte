<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6_uqk3gh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="t6_uqk3gh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrow-round-outline" {...props}></Icon>
