<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okmoa9bvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="okmoa9bvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:cross-outline" {...props}></Icon>
