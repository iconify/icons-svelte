<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7k49nwxu.css';
import '../../css/t/tkczr6bqo.css';
import '../../css/o/o3ighkj3w.css';
import '../../css/f/fdps2pjit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o7k49nwxu"/><path class="tkczr6bqo"/><path class="o3ighkj3w"/><path class="fdps2pjit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:clover-48" {...props}></Icon>
