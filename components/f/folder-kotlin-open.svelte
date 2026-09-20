<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ix3d72cff.css';
import '../../css/o/ogtj31bng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ix3d72cff"/><path class="ogtj31bng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-kotlin-open" {...props}></Icon>
