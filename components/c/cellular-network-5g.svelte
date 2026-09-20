<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq1hn912b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="uq1hn912b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:cellular-network-5g" {...props}></Icon>
