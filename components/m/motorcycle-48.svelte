<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dp6r5wbyh.css';
import '../../css/g/gtr6zk6db.css';
import '../../css/d/dl_nt7bof.css';
import '../../css/y/ydacol75i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dp6r5wbyh"/><path class="gtr6zk6db"/><path class="dl_nt7bof"/><path class="ydacol75i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:motorcycle-48" {...props}></Icon>
