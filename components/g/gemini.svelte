<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw_p06a2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lw_p06a2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:gemini" {...props}></Icon>
