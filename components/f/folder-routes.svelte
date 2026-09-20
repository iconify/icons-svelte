<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukvws-bxw.css';
import '../../css/e/edfie7bhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ukvws-bxw"/><path class="edfie7bhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-routes" {...props}></Icon>
