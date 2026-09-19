<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3_vnw0km.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m3_vnw0km"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:good-one" {...props}></Icon>
