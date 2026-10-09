<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahmy5tb-o.css';
import '../../css/o/o3s572blx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ahmy5tb-o"/><path class="o3s572blx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:copy-48-bold" {...props}></Icon>
