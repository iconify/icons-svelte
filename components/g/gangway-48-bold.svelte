<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt1i9cb7l.css';
import '../../css/x/xf50wgb4t.css';
import '../../css/t/tb4njgoat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xt1i9cb7l"/><path class="xf50wgb4t"/><path class="tb4njgoat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gangway-48-bold" {...props}></Icon>
