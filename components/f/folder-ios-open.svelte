<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzh5w72co.css';
import '../../css/k/kgcox8b6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tzh5w72co"/><path class="kgcox8b6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-ios-open" {...props}></Icon>
