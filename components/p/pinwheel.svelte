<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr_fy53ar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pr_fy53ar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:pinwheel" {...props}></Icon>
