<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hp7rzjb5c.css';
import '../../css/q/qk2qv3bmt.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGNcVFUBwS"><g class="ft5dv1b6b"><path class="hp7rzjb5c"/><path class="qk2qv3bmt"/></g></mask></defs><path mask="url(#SVGNcVFUBwS)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:google" {...props}></Icon>
