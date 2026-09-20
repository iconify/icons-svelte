<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsggtbcdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tsggtbcdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:octagram-shape-flat" {...props}></Icon>
