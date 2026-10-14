<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/o/ok_hdd46i.css';
import '../../css/r/r6jly0bva.css';
import '../../css/g/g8qaqv_gb.css';
import '../../css/u/ulldvebzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="ok_hdd46i"/><path class="r6jly0bva"/><path class="g8qaqv_gb"/><path class="ulldvebzg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:drafting-compass" {...props}></Icon>
