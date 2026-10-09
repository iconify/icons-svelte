<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv3v9_bgq.css';
import '../../css/w/wegdy5b4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kv3v9_bgq"/><path class="wegdy5b4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lng-ship-48" {...props}></Icon>
