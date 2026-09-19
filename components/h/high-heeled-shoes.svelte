<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/m/mnzhnhbdm.css';
import '../../css/i/iehr1opfa.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGWhrNKdWS"><g class="aql7dnt-u"><path class="mnzhnhbdm"/><path class="iehr1opfa"/></g></mask></defs><path mask="url(#SVGWhrNKdWS)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:high-heeled-shoes" {...props}></Icon>
