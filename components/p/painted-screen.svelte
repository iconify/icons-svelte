<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/s08vpub8u.css';
import '../../css/o/ojv2arocj.css';
import '../../css/m/mq5xx16sw.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGBi8LkdFe"><g class="ft5dv1b6b"><rect class="s08vpub8u"/><path class="ojv2arocj"/><rect transform="rotate(90 15 29)" class="mq5xx16sw"/></g></mask></defs><path mask="url(#SVGBi8LkdFe)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:painted-screen" {...props}></Icon>
