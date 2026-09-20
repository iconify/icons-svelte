<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ge-jeq6zd.css';
import '../../css/m/mexy6lbof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ge-jeq6zd"/><path class="mexy6lbof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-gradle-open" {...props}></Icon>
