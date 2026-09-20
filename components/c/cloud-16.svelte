<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbos_mlra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jbos_mlra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:cloud-16" {...props}></Icon>
