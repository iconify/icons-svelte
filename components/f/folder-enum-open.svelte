<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpc9hgrvp.css';
import '../../css/i/i3q4zpbdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mpc9hgrvp"/><path class="i3q4zpbdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-enum-open" {...props}></Icon>
