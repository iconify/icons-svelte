<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgtyx9bji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xgtyx9bji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:dumbbel-line" {...props}></Icon>
