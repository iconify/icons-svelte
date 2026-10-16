<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgupoibyg.css';
import '../../css/l/lkae4mbsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rgupoibyg"/><path class="lkae4mbsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:icicles-48" {...props}></Icon>
