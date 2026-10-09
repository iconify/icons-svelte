<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x813rhndo.css';
import '../../css/n/nvr1vcb4k.css';
import '../../css/b/bc-b47bac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x813rhndo"/><path class="nvr1vcb4k"/><path class="bc-b47bac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:paint-roller-48" {...props}></Icon>
