<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/t/tv8cojbtd.css';
import '../../css/m/m4ez7y5oo.css';
import '../../css/s/sy_aj1b_e.css';
import '../../css/d/dytkvhn7h.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGYFWnZlcI"><g class="v3_i3wktz"><path class="tv8cojbtd"/><path class="m4ez7y5oo"/><path class="sy_aj1b_e"/><path class="dytkvhn7h"/></g></mask></defs><path mask="url(#SVGYFWnZlcI)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:petrol" {...props}></Icon>
