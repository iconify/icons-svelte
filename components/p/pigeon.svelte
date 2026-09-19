<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nbav1obyp.css';
import '../../css/w/wm8gb-9hv.css';
import '../../css/u/u2q07cbcb.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGVSzTtc9I"><g class="ft5dv1b6b"><path class="nbav1obyp"/><path class="wm8gb-9hv"/><circle class="u2q07cbcb"/></g></mask></defs><path mask="url(#SVGVSzTtc9I)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:pigeon" {...props}></Icon>
