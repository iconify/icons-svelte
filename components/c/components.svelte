<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl-kk3btk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tl-kk3btk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:components" {...props}></Icon>
