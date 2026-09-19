<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3ht4pbgq.css';
import '../../css/j/jqc7hmb-f.css';
import '../../css/z/zoar6acpn.css';
import '../../css/l/lrhlp9bgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="o3ht4pbgq"/><path class="jqc7hmb-f"/><path class="zoar6acpn"/><path class="lrhlp9bgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:gpx-file" {...props}></Icon>
