<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av9yo2bgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="av9yo2bgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:box-close-outline" {...props}></Icon>
