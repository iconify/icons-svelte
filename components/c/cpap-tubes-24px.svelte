<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2f-vv4ph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y2f-vv4ph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:cpap-tubes-24px" {...props}></Icon>
