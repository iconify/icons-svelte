<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2if9lbnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="m2if9lbnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrow-circle-bold" {...props}></Icon>
