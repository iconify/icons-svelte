<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/w/wrhmw8bod.css';
import '../../css/m/mes17gbuk.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGtLx6gcYu"><g class="aql7dnt-u"><path class="wrhmw8bod"/><circle class="mes17gbuk"/></g></mask></defs><path mask="url(#SVGtLx6gcYu)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:connect-address-two" {...props}></Icon>
