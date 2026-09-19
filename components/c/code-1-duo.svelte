<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yq8q-ltfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="yq8q-ltfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:code-1-duo" {...props}></Icon>
