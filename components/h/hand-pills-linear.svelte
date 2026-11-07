<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/r/rjfa6f3hs.css';
import '../../css/z/z_r9jpb7p.css';
import '../../css/a/a3scpvo1f.css';
import '../../css/e/eck4ylbag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="rjfa6f3hs"/><path class="z_r9jpb7p"/><path class="a3scpvo1f"/><path class="eck4ylbag"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hand-pills-linear" {...props}></Icon>
