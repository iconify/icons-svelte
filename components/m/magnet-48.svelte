<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gll0cba2f.css';
import '../../css/z/zmxd02b8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gll0cba2f"/><path class="zmxd02b8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:magnet-48" {...props}></Icon>
