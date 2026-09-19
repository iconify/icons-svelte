<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/a/auzy0hbwl.css';
import '../../css/i/ivargsbvq.css';
import '../../css/s/s_6zp33hf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="auzy0hbwl"/><path class="ivargsbvq"/><path class="s_6zp33hf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:cogs" {...props}></Icon>
