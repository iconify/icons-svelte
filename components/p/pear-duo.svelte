<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbza5obpu.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/q9mhg2b_r.css';
import '../../css/o/o92xprdlg.css';
import '../../css/p/pdz0srsgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gbza5obpu secondary"/><g class="dt0cm9dhy primary"><path class="q9mhg2b_r"/><path class="o92xprdlg"/><path class="pdz0srsgu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pear-duo" {...props}></Icon>
