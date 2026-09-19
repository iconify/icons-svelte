<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/f/fqsvnfbdg.css';
import '../../css/e/e7dr5zbeu.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGh5aOocYS"><g class="v3_i3wktz"><rect class="fqsvnfbdg"/><path class="e7dr5zbeu"/></g></mask></defs><path mask="url(#SVGh5aOocYS)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:electronic-locks-close" {...props}></Icon>
