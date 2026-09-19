<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vl0sbknne.css';
import '../../css/i/ir6ml4blk.css';
import '../../css/a/anbnfobac.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGVlQBebkA"><g class="ft5dv1b6b"><path clip-rule="evenodd" class="vl0sbknne"/><path class="ir6ml4blk"/><path clip-rule="evenodd" class="anbnfobac"/></g></mask></defs><path mask="url(#SVGVlQBebkA)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:painted-eggshell" {...props}></Icon>
