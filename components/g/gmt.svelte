<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/ulbgvyh1o.css';
import '../../css/m/md286fbip.css';
import '../../css/o/os1s_jbru.css';
import '../../css/q/q7o01wbuj.css';
import '../../css/m/ml_vzybbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle class="ulbgvyh1o"/><g class="md286fbip"><path class="os1s_jbru"/><path class="q7o01wbuj"/><path class="ml_vzybbu"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:gmt" {...props}></Icon>
