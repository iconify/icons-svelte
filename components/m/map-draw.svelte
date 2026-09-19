<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwvp95byt.css';
import '../../css/q/qz06jbkqv.css';
import '../../css/b/b4qpfgbcg.css';
import '../../css/q/q0fvvybgc.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGUyQBvdTQ"><g class="wwvp95byt"><path class="qz06jbkqv"/><path class="b4qpfgbcg"/><path class="q0fvvybgc"/></g></mask></defs><path mask="url(#SVGUyQBvdTQ)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:map-draw" {...props}></Icon>
