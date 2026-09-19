<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hu0___bzk.css';
import '../../css/q/q0ugzngzb.css';
import '../../css/s/staoijb6t.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGz8BPDc2k"><g class="ft5dv1b6b"><rect class="hu0___bzk"/><path clip-rule="evenodd" class="q0ugzngzb"/><path class="staoijb6t"/></g></mask></defs><path mask="url(#SVGz8BPDc2k)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:equal-ratio" {...props}></Icon>
