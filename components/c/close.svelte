<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-r2anv0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m-r2anv0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:close" {...props}></Icon>
