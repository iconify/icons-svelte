<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/a/axvwh0bez.css';
import '../../css/c/cczcib67m.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGEDpbBe5z"><g class="v3_i3wktz"><path class="axvwh0bez"/><path clip-rule="evenodd" class="cczcib67m"/></g></mask></defs><path mask="url(#SVGEDpbBe5z)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:book" {...props}></Icon>
