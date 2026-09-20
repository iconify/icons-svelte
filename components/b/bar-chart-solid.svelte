<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlxnel37i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="wlxnel37i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:bar-chart-solid" {...props}></Icon>
