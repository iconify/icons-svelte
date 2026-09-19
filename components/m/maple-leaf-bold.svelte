<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo5-_oboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="qo5-_oboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:maple-leaf-bold" {...props}></Icon>
