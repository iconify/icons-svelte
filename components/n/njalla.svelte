<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlvmpt37w.css';
import '../../css/m/matknhssk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vlvmpt37w"/><path class="matknhssk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:njalla" {...props}></Icon>
