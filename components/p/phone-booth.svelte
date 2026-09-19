<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/o/oib7atbgf.css';
import '../../css/a/aoxssybqm.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGyH3hlcdP"><g class="aql7dnt-u"><path class="oib7atbgf"/><path class="aoxssybqm"/></g></mask></defs><path mask="url(#SVGyH3hlcdP)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:phone-booth" {...props}></Icon>
