<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/p/prztxk67h.css';
import '../../css/s/st0k6jbed.css';
import '../../css/y/y-a0iibgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="prztxk67h"/><path class="st0k6jbed"/><path class="y-a0iibgi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:album-collection" {...props}></Icon>
