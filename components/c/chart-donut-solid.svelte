<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/i/ir9gk0bmw.css';
import '../../css/p/pmzhwwgdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path class="ir9gk0bmw"/><path class="pmzhwwgdw wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chart-donut-solid" {...props}></Icon>
