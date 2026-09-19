<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k4cxfdbcp.css';
import '../../css/j/juh0nb25u.css';
import '../../css/o/owe8oibat.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGHlvrxbht"><g class="ft5dv1b6b"><path clip-rule="evenodd" class="k4cxfdbcp"/><path class="juh0nb25u"/><path clip-rule="evenodd" class="owe8oibat"/></g></mask></defs><path mask="url(#SVGHlvrxbht)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:painted-eggshell" {...props}></Icon>
