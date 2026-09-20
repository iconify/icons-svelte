<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7-c3zb9h.css';
import '../../css/m/mexy6lbof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v7-c3zb9h"/><path class="mexy6lbof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-gradle" {...props}></Icon>
