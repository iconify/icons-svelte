<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pk3045bun.css';
import '../../css/q/q0fujjtaq.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGxzvDJH5C"><g class="ft5dv1b6b"><path class="pk3045bun"/><path class="q0fujjtaq"/></g></mask></defs><path mask="url(#SVGxzvDJH5C)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:battery-empty" {...props}></Icon>
