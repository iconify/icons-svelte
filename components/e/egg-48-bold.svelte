<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bulyt4ubp.css';
import '../../css/n/n6-nt1bjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bulyt4ubp"/><path class="n6-nt1bjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:egg-48-bold" {...props}></Icon>
