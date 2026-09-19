<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2j8v34kx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e2j8v34kx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:layout-sidebar-left" {...props}></Icon>
