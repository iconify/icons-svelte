<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7vsp1bys.css';
import '../../css/u/u2bj5pb5k.css';
import '../../css/l/lutt4cc1w.css';
import '../../css/d/d8c64zbxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l7vsp1bys"/><path class="u2bj5pb5k"/><path class="lutt4cc1w"/><path class="d8c64zbxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydrogen-bus-48" {...props}></Icon>
