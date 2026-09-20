<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpnn3uu-g.css';
import '../../css/j/jletztwxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tpnn3uu-g"/><path class="jletztwxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:project-symlink-16" {...props}></Icon>
