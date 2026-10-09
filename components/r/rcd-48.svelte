<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp-8xbcar.css';
import '../../css/l/luu7bn_8g.css';
import '../../css/b/btws7t3pu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mp-8xbcar"/><path class="luu7bn_8g"/><path class="btws7t3pu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rcd-48" {...props}></Icon>
