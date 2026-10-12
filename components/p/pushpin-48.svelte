<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf93xsbmn.css';
import '../../css/k/kjf3iqboc.css';
import '../../css/f/fmo52ol9d.css';
import '../../css/t/t2smvv9rt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pf93xsbmn"/><path class="kjf3iqboc"/><path class="fmo52ol9d"/><path class="t2smvv9rt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pushpin-48" {...props}></Icon>
