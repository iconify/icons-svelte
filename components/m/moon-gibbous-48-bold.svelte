<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdlgrw2ra.css';
import '../../css/o/o26qb2bal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pdlgrw2ra"/><path class="o26qb2bal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:moon-gibbous-48-bold" {...props}></Icon>
