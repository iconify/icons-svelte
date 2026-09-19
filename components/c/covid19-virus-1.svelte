<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/b/bip1gyzkx.css';
import '../../css/l/ll5ebi28y.css';
import '../../css/z/z2g23rxag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="bip1gyzkx"/><path class="ll5ebi28y"/><path class="z2g23rxag"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:covid19-virus-1" {...props}></Icon>
