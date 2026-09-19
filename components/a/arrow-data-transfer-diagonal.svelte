<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilq3p7wvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilq3p7wvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-data-transfer-diagonal" {...props}></Icon>
