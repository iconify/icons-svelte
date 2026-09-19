<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/e/e3_0itu4g.css';
import '../../css/u/u-br6yhtk.css';
import '../../css/z/zct82vb9f.css';
import '../../css/f/fll0uqb6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="e3_0itu4g"/><path class="u-br6yhtk"/><path class="zct82vb9f"/><path class="fll0uqb6i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:covid19-virus-warning-2" {...props}></Icon>
