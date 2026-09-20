<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msnernbby.css';
import '../../css/q/qw35iee-y.css';
import '../../css/s/s4kdj5j1y.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/b/bw1cmbb3h.css';
import '../../css/y/y5m0rdbxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="msnernbby"/><path class="qw35iee-y"/><path class="s4kdj5j1y"/><g class="jn8qy4bru"><path class="bw1cmbb3h"/><path class="y5m0rdbxf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:rock" {...props}></Icon>
