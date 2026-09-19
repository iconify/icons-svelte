<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6z0wd76j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="a6z0wd76j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:chart-bar-1-outline" {...props}></Icon>
