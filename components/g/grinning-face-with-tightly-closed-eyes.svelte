<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/o/oo_vs07_g.css';
import '../../css/x/xn262ubam.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGUIZUEboM"><g class="ufeehvblu"><path class="oo_vs07_g"/><path class="xn262ubam"/></g></mask></defs><path mask="url(#SVGUIZUEboM)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:grinning-face-with-tightly-closed-eyes" {...props}></Icon>
