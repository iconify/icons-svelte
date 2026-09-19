<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yoip6sbuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="yoip6sbuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:h-outline" {...props}></Icon>
