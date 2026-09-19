<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rgf3yzrlx.css';
import '../../css/z/zjo5c8brt.css';
import '../../css/c/cfgqxmsis.css';
import '../../css/c/c8ldgsbvq.css';
import '../../css/l/l7kc-dbmz.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGKTbkbbBA"><g class="ft5dv1b6b"><circle class="rgf3yzrlx"/><path class="zjo5c8brt"/><path class="cfgqxmsis"/><path class="c8ldgsbvq"/><path class="l7kc-dbmz"/></g></mask></defs><path mask="url(#SVGKTbkbbBA)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:bitcoin" {...props}></Icon>
