<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_pz3rxhk.css';
import '../../css/i/iha0k5bup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y_pz3rxhk"/><path class="iha0k5bup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:esg-report-48-bold" {...props}></Icon>
