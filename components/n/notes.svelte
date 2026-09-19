<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/n/nts37w2-y.css';
import '../../css/i/ir8prxc9v.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGFo46TdoW"><g class="v3_i3wktz"><path class="nts37w2-y"/><path class="ir8prxc9v"/></g></mask></defs><path mask="url(#SVGFo46TdoW)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:notes" {...props}></Icon>
