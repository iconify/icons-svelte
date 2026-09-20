<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dypv3-mdc.css';
import '../../css/q/qg_93a6ly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dypv3-mdc"/><path class="qg_93a6ly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-scripts" {...props}></Icon>
