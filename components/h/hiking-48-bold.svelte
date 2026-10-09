<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi-w-lr1f.css';
import '../../css/d/db7c96bxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bi-w-lr1f"/><path class="db7c96bxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hiking-48-bold" {...props}></Icon>
