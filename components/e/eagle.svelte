<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cvdlkkmwq.css';
import '../../css/l/lg4joxb9h.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGPvIAkcLy"><g class="ft5dv1b6b"><path class="cvdlkkmwq"/><circle class="lg4joxb9h"/></g></mask></defs><path mask="url(#SVGPvIAkcLy)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:eagle" {...props}></Icon>
