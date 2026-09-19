<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdt38crvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bdt38crvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:filter-one" {...props}></Icon>
