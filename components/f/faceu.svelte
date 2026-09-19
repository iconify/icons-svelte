<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/afeo2fbqa.css';
import '../../css/r/rbxch99hb.css';
import '../../css/o/oe3u2eq0u.css';
import '../../css/a/aw231xbym.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGfqvSaccR"><g class="ft5dv1b6b"><path class="afeo2fbqa"/><path class="rbxch99hb"/><ellipse class="oe3u2eq0u"/><ellipse class="aw231xbym"/></g></mask></defs><path mask="url(#SVGfqvSaccR)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:faceu" {...props}></Icon>
