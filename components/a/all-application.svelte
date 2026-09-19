<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lksn13b0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lksn13b0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:all-application" {...props}></Icon>
