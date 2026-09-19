<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm29z5bmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hm29z5bmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:layout-sidebar-right" {...props}></Icon>
