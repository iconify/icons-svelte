<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dypv3-mdc.css';
import '../../css/o/ocb02aciv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dypv3-mdc"/><path class="ocb02aciv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-next" {...props}></Icon>
