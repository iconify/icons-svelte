<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydne_bc6v.css';
import '../../css/l/l3c9lplte.css';
import '../../css/j/jebph_z3j.css';
import '../../css/v/v6eawsb5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ydne_bc6v"><path class="l3c9lplte"/><path class="jebph_z3j"/><path class="v6eawsb5q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:notification-alarm-snooze" {...props}></Icon>
