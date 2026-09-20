<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xads-bcdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xads-bcdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-transfer-outline" {...props}></Icon>
