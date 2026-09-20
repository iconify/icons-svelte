<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-sjs80hz.css';
import '../../css/y/yg4ntub0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e-sjs80hz"/><circle class="yg4ntub0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:livinity-light" {...props}></Icon>
