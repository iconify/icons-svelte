<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xixnvzb-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xixnvzb-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:decimals-arrow-right" {...props}></Icon>
