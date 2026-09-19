<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hi7ctob3t.css';
import '../../css/r/r_bjxzwmx.css';
import '../../css/i/i-ryefrpq.css';
import '../../css/d/diikp8b7z.css';
import '../../css/i/i71l6dtrl.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG3dtSYjIs"><g class="ft5dv1b6b"><path class="hi7ctob3t"/><path clip-rule="evenodd" class="r_bjxzwmx"/><path class="i-ryefrpq"/><path clip-rule="evenodd" class="diikp8b7z"/><path class="i71l6dtrl"/></g></mask></defs><path mask="url(#SVG3dtSYjIs)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:dislike-two" {...props}></Icon>
