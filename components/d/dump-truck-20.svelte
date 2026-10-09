<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whrwdskwh.css';
import '../../css/a/ao3d_1b-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="whrwdskwh"/><path class="ao3d_1b-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dump-truck-20" {...props}></Icon>
