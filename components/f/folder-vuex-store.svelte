<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufv-l2b0j.css';
import '../../css/n/nu_6q77ce.css';
import '../../css/n/nrcaqmbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ufv-l2b0j"/><path class="nu_6q77ce"/><path class="nrcaqmbsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-vuex-store" {...props}></Icon>
