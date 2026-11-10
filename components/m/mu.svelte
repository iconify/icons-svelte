<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/r/r4blj6b3g.css';
import '../../css/n/njphwbz6x.css';
import '../../css/o/ohcwwnbis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="r4blj6b3g"/><path class="njphwbz6x"/><path class="ohcwwnbis"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:mu" {...props}></Icon>
