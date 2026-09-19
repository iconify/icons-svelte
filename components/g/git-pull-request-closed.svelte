<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/l/l1hgzkxik.css';
import '../../css/s/sa8oq8bea.css';
import '../../css/n/ng521n2fi.css';
import '../../css/n/nmoouyb9r.css';
import '../../css/x/xywnlchxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="l1hgzkxik"/><circle class="sa8oq8bea"/><circle class="ng521n2fi"/><circle class="nmoouyb9r"/><path class="xywnlchxf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:git-pull-request-closed" {...props}></Icon>
