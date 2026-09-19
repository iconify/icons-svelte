<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/f/fr8naq4ou.css';
import '../../css/l/lz2_s1bck.css';
import '../../css/m/m5znx-b1e.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGqkBKucJk"><g class="v3_i3wktz"><path class="fr8naq4ou"/><path class="lz2_s1bck"/><path class="m5znx-b1e"/></g></mask></defs><path mask="url(#SVGqkBKucJk)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:coffee-machine" {...props}></Icon>
