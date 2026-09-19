<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2-2uepmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r2-2uepmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:left-small" {...props}></Icon>
