<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1_swcb_o.css';
import '../../css/p/p-3d8dotc.css';
import '../../css/f/f9rt4jovo.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGQbdUXdPh"><g class="v1_swcb_o"><path class="p-3d8dotc"/><path class="f9rt4jovo"/></g></mask></defs><path mask="url(#SVGQbdUXdPh)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:health" {...props}></Icon>
