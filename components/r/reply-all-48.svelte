<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdxdnnz1r.css';
import '../../css/p/pggd_gbcs.css';
import '../../css/r/r-m9obb9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mdxdnnz1r"/><path class="pggd_gbcs"/><path class="r-m9obb9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:reply-all-48" {...props}></Icon>
