<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/a/a1ag6vmcj.css';
import '../../css/h/h7nduwp1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="pie-chart-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="a1ag6vmcj"/><path class="h7nduwp1f"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:pie-chart-outline" {...props}></Icon>
