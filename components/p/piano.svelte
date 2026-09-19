<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unqi43f2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="unqi43f2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:piano" {...props}></Icon>
