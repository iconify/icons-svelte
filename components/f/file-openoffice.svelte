<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbyl9fxpo.css';
import '../../css/x/xnk1gt9lb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mbyl9fxpo"/><path class="xnk1gt9lb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:file-openoffice" {...props}></Icon>
