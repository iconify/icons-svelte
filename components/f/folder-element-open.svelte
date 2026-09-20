<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkb61lbnd.css';
import '../../css/u/uwu1irugu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dkb61lbnd"/><path class="uwu1irugu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-element-open" {...props}></Icon>
