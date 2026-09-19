<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgpe9kb6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rgpe9kb6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:bar-chart" {...props}></Icon>
