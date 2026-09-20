<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkb61lbnd.css';
import '../../css/z/zn2buv2un.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dkb61lbnd"/><path class="zn2buv2un"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-ui-open" {...props}></Icon>
