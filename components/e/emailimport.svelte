<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tei0bgeom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tei0bgeom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:emailimport" {...props}></Icon>
