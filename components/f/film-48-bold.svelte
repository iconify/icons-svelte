<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy7xqk_um.css';
import '../../css/x/xp2kcen4h.css';
import '../../css/t/tou7l3b1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xy7xqk_um"/><path class="xp2kcen4h"/><path class="tou7l3b1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:film-48-bold" {...props}></Icon>
