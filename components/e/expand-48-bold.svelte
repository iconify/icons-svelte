<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gk_btpb8m.css';
import '../../css/s/s-anv9bde.css';
import '../../css/h/hfommxotc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gk_btpb8m"/><path class="s-anv9bde"/><path class="hfommxotc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:expand-48-bold" {...props}></Icon>
