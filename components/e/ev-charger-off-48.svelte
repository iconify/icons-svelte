<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6awtztgo.css';
import '../../css/i/i_htz80rx.css';
import '../../css/p/p7kyn66pi.css';
import '../../css/y/y-u291bfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s6awtztgo"/><path class="i_htz80rx"/><path class="p7kyn66pi"/><path class="y-u291bfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ev-charger-off-48" {...props}></Icon>
