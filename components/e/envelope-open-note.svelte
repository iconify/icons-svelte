<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/a/azmt7fbec.css';
import '../../css/h/h6i762oyw.css';
import '../../css/s/sq30kocpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="azmt7fbec"/><path class="h6i762oyw"/><path class="sq30kocpx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:envelope-open-note" {...props}></Icon>
