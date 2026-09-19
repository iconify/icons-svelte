<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzve_6a2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zzve_6a2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:add-item" {...props}></Icon>
