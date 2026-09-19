<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmaojwd9t.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG0F4f16iy"><path class="hmaojwd9t"/></mask></defs><path mask="url(#SVG0F4f16iy)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:fist" {...props}></Icon>
