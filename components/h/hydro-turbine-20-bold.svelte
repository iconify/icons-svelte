<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qc3aivm8q.css';
import '../../css/j/jvlfvgboy.css';
import '../../css/w/woe8reb4u.css';
import '../../css/y/yntic7bpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qc3aivm8q"/><path class="jvlfvgboy"/><path class="woe8reb4u"/><path class="yntic7bpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydro-turbine-20-bold" {...props}></Icon>
