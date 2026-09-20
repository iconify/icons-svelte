<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj614lbop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bj614lbop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:hierarchy-1" {...props}></Icon>
