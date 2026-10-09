<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdos38jip.css';
import '../../css/p/p1kcgj3tk.css';
import '../../css/y/ywhth4bre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pdos38jip"/><path class="p1kcgj3tk"/><path class="ywhth4bre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-plus-48-bold" {...props}></Icon>
