<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vv07cqboy.css';
import '../../css/n/nwofm8dpb.css';
import '../../css/c/c_w4rabif.css';
import '../../css/u/uk_tlyd7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="vv07cqboy"/><path clip-rule="evenodd" class="nwofm8dpb"/><path class="c_w4rabif"/><path clip-rule="evenodd" class="uk_tlyd7k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:archive-outline" {...props}></Icon>
