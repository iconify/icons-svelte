<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2s12l6ub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c2s12l6ub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:file-import-outline" {...props}></Icon>
