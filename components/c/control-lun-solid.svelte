<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu410db3i.css';
import '../../css/u/u4lsadx-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="mu410db3i"/><path class="u4lsadx-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:control-lun-solid" {...props}></Icon>
