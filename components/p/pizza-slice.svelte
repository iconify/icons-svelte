<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/m/m6pkdzb0p.css';
import '../../css/j/jbfeyeo7i.css';
import '../../css/x/x6-sqeb_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="m6pkdzb0p"/><path class="jbfeyeo7i"/><path class="x6-sqeb_l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:pizza-slice" {...props}></Icon>
