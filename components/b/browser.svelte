<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n2b3f1bel.css';
import '../../css/b/bbxz0jq4i.css';
import '../../css/q/qtskb2sji.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGXHvbndxd"><g class="ft5dv1b6b"><path class="n2b3f1bel"/><path class="bbxz0jq4i"/><path clip-rule="evenodd" class="qtskb2sji"/></g></mask></defs><path mask="url(#SVGXHvbndxd)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:browser" {...props}></Icon>
