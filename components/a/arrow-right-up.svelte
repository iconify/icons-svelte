<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py8pa3bbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="py8pa3bbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:arrow-right-up" {...props}></Icon>
