<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdbcpwbxd.css';
import '../../css/z/zso3njb9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qdbcpwbxd"/><path class="zso3njb9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-bolt-20" {...props}></Icon>
