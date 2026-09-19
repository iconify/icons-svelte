<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjmja5ggc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yjmja5ggc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:pinwheel" {...props}></Icon>
